<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8w6b6l9s.css';
import '../../css/i/i1aaxkb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a8w6b6l9s"/><path class="i1aaxkb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plug-uk-48" {...props}></Icon>
