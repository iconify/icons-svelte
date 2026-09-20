<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wntam8p1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wntam8p1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-bars" {...props}></Icon>
