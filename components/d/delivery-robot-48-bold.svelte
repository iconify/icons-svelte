<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twlufw5gg.css';
import '../../css/w/wr4720bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="twlufw5gg"/><path class="wr4720bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:delivery-robot-48-bold" {...props}></Icon>
