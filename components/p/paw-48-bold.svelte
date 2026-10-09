<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hda81ubct.css';
import '../../css/o/ot3162boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hda81ubct"/><path class="ot3162boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paw-48-bold" {...props}></Icon>
