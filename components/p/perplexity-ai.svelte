<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v331ncoop.css';
import '../../css/o/oe6jpabdk.css';
import '../../css/x/xy26lsb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v331ncoop"/><path class="oe6jpabdk"/><path class="xy26lsb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:perplexity-ai" {...props}></Icon>
