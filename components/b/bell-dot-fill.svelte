<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgmkij3-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="xgmkij3-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bell-dot-fill" {...props}></Icon>
