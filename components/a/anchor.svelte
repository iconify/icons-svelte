<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyfzb6bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eyfzb6bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:anchor" {...props}></Icon>
