<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9v47kbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q9v47kbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:diamond-48" {...props}></Icon>
