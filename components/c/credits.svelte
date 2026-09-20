<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q54ebz0wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q54ebz0wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:credits" {...props}></Icon>
