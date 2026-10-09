<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_yowkbgo.css';
import '../../css/f/fdc56liyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c_yowkbgo"/><path class="fdc56liyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:contact-48-bold" {...props}></Icon>
