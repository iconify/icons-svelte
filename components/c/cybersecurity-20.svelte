<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc9itcbez.css';
import '../../css/d/d_av7khvm.css';
import '../../css/y/ymo2yhixw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sc9itcbez"/><path class="d_av7khvm"/><path class="ymo2yhixw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cybersecurity-20" {...props}></Icon>
