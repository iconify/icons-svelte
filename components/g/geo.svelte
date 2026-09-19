<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-_pmti1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a-_pmti1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:geo" {...props}></Icon>
