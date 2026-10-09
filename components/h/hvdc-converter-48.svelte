<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f76ef2b7k.css';
import '../../css/s/s0byieb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f76ef2b7k"/><path class="s0byieb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hvdc-converter-48" {...props}></Icon>
