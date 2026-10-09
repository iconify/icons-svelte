<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2irslbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g2irslbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-left-48-bold" {...props}></Icon>
