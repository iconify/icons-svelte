<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlm5yub9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlm5yub9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:heart-arrow-down" {...props}></Icon>
