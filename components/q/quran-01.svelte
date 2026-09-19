<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s51np_b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s51np_b-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:quran-01" {...props}></Icon>
