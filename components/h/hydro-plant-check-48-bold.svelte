<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc-70lbob.css';
import '../../css/b/b-pvjkb6t.css';
import '../../css/t/tvsqsyb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vc-70lbob"/><path class="b-pvjkb6t"/><path class="tvsqsyb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydro-plant-check-48-bold" {...props}></Icon>
