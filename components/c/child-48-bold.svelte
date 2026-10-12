<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj1-uqbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hj1-uqbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:child-48-bold" {...props}></Icon>
