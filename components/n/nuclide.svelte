<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luegz3bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":427,"height":512};
const content = `<path class="luegz3bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nuclide" {...props}></Icon>
