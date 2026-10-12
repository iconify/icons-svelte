<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsp7zgb3m.css';
import '../../css/w/wo7e92b0f.css';
import '../../css/m/min81mbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fsp7zgb3m"/><path class="wo7e92b0f"/><path class="min81mbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dna-20-bold" {...props}></Icon>
