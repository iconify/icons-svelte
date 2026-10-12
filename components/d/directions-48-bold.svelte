<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqnn4pbcu.css';
import '../../css/y/ykmr2x2jm.css';
import '../../css/c/cc2lz2byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iqnn4pbcu"/><path class="ykmr2x2jm"/><path class="cc2lz2byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:directions-48-bold" {...props}></Icon>
