<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0gi2-buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0gi2-buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ideogram" {...props}></Icon>
