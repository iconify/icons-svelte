<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf30sijas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lf30sijas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-drizzle-fill" {...props}></Icon>
