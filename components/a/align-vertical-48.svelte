<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia5lbtbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ia5lbtbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-vertical-48" {...props}></Icon>
