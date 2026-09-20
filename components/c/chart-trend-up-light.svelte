<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhr7z3b6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhr7z3b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chart-trend-up-light" {...props}></Icon>
