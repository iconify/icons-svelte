<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu6lcp3xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tu6lcp3xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:filter" {...props}></Icon>
