<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpzidqbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qpzidqbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grip-vertical-48" {...props}></Icon>
