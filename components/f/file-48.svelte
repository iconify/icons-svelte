<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dezwopb-j.css';
import '../../css/v/v5f8zgbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dezwopb-j"/><path class="v5f8zgbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-48" {...props}></Icon>
