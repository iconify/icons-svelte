<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emsq_7iza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="emsq_7iza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:pentagon-one" {...props}></Icon>
