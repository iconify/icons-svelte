<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9f-pebyy.css';
import '../../css/a/aaw7kqsgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m9f-pebyy"/><path class="aaw7kqsgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:door-48-bold" {...props}></Icon>
