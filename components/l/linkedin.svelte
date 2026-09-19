<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kogk3ac4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":480};
const content = `<path class="kogk3ac4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:linkedin" {...props}></Icon>
