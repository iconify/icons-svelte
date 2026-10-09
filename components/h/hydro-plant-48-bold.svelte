<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc-70lbob.css';
import '../../css/u/ul7pjw58j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vc-70lbob"/><path class="ul7pjw58j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydro-plant-48-bold" {...props}></Icon>
