<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksksr155x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ksksr155x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chevron-compact-left" {...props}></Icon>
