<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz13tcbgt.css';
import '../../css/h/h6zvdsy7j.css';
import '../../css/k/kymxsbbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cz13tcbgt"/><path class="h6zvdsy7j"/><path class="kymxsbbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-landing-48-bold" {...props}></Icon>
