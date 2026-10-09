<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fko3tyrmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fko3tyrmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:check-48-bold" {...props}></Icon>
