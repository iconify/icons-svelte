<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsv5h1yxl.css';
import '../../css/r/r67i5vbwt.css';
import '../../css/f/f2v26bkcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gsv5h1yxl"/><path class="r67i5vbwt"/><path class="f2v26bkcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-charger-home-48-bold" {...props}></Icon>
