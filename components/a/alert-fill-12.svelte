<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8p0unujj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z8p0unujj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:alert-fill-12" {...props}></Icon>
