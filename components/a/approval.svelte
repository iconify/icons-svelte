<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfwf8-3ye.css';
import '../../css/a/az0bq2bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wfwf8-3ye"/><path class="az0bq2bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:approval" {...props}></Icon>
