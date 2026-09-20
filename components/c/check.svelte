<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1btt3j3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="z1btt3j3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:check" {...props}></Icon>
