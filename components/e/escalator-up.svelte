<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvw_5zbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uvw_5zbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:escalator-up" {...props}></Icon>
