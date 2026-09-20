<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo75l1ond.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo75l1ond"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chart-trend-down-solid" {...props}></Icon>
