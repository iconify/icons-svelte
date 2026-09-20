<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqfxqwb8y.css';
import '../../css/v/vd40rwvyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jqfxqwb8y"/><path class="vd40rwvyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:postal-dark" {...props}></Icon>
