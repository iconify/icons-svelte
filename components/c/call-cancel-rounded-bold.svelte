<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-r_0lb5z.css';
import '../../css/c/cfzav0mxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-r_0lb5z"/><path class="cfzav0mxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-cancel-rounded-bold" {...props}></Icon>
