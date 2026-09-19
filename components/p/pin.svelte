<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8aaw68sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8aaw68sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:pin" {...props}></Icon>
