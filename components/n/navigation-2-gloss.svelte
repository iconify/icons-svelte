<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh4-wacdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh4-wacdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:navigation-2-gloss" {...props}></Icon>
