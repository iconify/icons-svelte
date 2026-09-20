<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6zmhvbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k6zmhvbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:paragraph-8" {...props}></Icon>
