<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4_y_kbip.css';
import '../../css/q/qpe8ekbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f4_y_kbip"/><path class="qpe8ekbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paragraph-48-bold" {...props}></Icon>
