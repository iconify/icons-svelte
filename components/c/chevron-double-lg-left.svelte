<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y086wwr5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y086wwr5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:chevron-double-lg-left" {...props}></Icon>
