<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwfalccns.css';
import '../../css/v/v4w_f_aee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rwfalccns"/><path class="v4w_f_aee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carabiner-20" {...props}></Icon>
