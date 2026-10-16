<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df4gvuaqr.css';
import '../../css/f/friicz-ai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="df4gvuaqr"/><path class="friicz-ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-reducer-48" {...props}></Icon>
