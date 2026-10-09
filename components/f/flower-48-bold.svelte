<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7kleu9_v.css';
import '../../css/m/mn53fqbfv.css';
import '../../css/u/ulvulp3em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l7kleu9_v"/><path class="mn53fqbfv"/><path class="ulvulp3em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flower-48-bold" {...props}></Icon>
