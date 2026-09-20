<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng_2knrqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ng_2knrqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-expand-solid" {...props}></Icon>
