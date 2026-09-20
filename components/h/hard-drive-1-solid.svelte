<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wetrx5beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wetrx5beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hard-drive-1-solid" {...props}></Icon>
