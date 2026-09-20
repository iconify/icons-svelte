<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu8sa6bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hu8sa6bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:factorial-solid" {...props}></Icon>
