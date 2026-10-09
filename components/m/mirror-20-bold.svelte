<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqrfxzblb.css';
import '../../css/e/e5nrzwjsg.css';
import '../../css/f/fh8bft_rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fqrfxzblb"/><path class="e5nrzwjsg"/><path class="fh8bft_rz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mirror-20-bold" {...props}></Icon>
