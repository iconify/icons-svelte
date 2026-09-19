<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgbsv---w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgbsv---w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrange-by-letters-z-a" {...props}></Icon>
