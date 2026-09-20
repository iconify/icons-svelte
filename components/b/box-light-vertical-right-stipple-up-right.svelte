<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-3qw_iec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="n-3qw_iec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-right-stipple-up-right" {...props}></Icon>
