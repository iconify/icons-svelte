<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gac1gm6_a.css';
import '../../css/l/lf-esqlup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gac1gm6_a"/><path class="lf-esqlup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:funnel-match-ltr" {...props}></Icon>
