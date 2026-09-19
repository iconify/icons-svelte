<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_5qddr-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k_5qddr-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:bars-ascending-align-left" {...props}></Icon>
