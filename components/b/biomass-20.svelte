<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucvn8mbai.css';
import '../../css/k/k220q4beo.css';
import '../../css/j/j2pm5abdo.css';
import '../../css/l/l2mw_ubua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ucvn8mbai"/><path class="k220q4beo"/><path class="j2pm5abdo"/><path class="l2mw_ubua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:biomass-20" {...props}></Icon>
