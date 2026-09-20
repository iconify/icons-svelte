<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moduqacij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="moduqacij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:circle-slash-16" {...props}></Icon>
