<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/resxiwg2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="resxiwg2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:hand-pointer-2-line" {...props}></Icon>
