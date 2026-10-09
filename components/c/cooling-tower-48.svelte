<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shh92ibos.css';
import '../../css/h/hw51tgbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="shh92ibos"/><path class="hw51tgbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cooling-tower-48" {...props}></Icon>
