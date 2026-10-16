<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f36_sk0cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f36_sk0cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:focus-48" {...props}></Icon>
