<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_zuvlbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="d_zuvlbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:car-dealer" {...props}></Icon>
