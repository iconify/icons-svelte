<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx2z66weu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mx2z66weu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:cross-reference-16" {...props}></Icon>
