<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onth24bvb.css';
import '../../css/q/qaw1fhbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="onth24bvb"/><path class="ouiIcon__fillSecondary qaw1fhbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-metrics" {...props}></Icon>
