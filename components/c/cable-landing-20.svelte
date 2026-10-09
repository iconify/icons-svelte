<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd7xtmwmp.css';
import '../../css/v/v33j91b-f.css';
import '../../css/w/wo9nd_b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rd7xtmwmp"/><path class="v33j91b-f"/><path class="wo9nd_b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-landing-20" {...props}></Icon>
