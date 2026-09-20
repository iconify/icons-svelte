<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh8byk_qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kh8byk_qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:map-marker" {...props}></Icon>
