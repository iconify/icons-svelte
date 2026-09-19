<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is07h1_2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="is07h1_2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:chevron-right" {...props}></Icon>
