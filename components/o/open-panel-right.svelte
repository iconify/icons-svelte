<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh99os3ic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dh99os3ic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:open-panel-right" {...props}></Icon>
