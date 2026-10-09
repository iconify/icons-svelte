<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auuyt2boe.css';
import '../../css/n/nfapznoxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="auuyt2boe"/><path class="nfapznoxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:camera-48" {...props}></Icon>
