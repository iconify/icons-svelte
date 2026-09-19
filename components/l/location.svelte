<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poltb9j9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="poltb9j9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:location" {...props}></Icon>
