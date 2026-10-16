<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqd7lbb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vqd7lbb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-sun-rain-48-bold" {...props}></Icon>
