<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqi8izblt.css';
import '../../css/e/emg8x4zsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eqi8izblt"/><path class="emg8x4zsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-location-48-bold" {...props}></Icon>
