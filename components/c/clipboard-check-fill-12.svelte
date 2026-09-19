<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3z1ddf_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="c3z1ddf_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clipboard-check-fill-12" {...props}></Icon>
