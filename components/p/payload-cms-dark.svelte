<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peby3jb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="peby3jb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:payload-cms-dark" {...props}></Icon>
