<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhb3nmbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hhb3nmbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:check-check-48" {...props}></Icon>
