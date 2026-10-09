<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4-c966ww.css';
import '../../css/a/au8t5v7zm.css';
import '../../css/g/gk48d415h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h4-c966ww"/><path class="au8t5v7zm"/><path class="gk48d415h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:factory-48" {...props}></Icon>
