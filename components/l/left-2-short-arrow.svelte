<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv2q-whaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv2q-whaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:left-2-short-arrow" {...props}></Icon>
