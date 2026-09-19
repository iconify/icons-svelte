<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yefscxbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="yefscxbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:mobile" {...props}></Icon>
