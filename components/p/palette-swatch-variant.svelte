<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw6-f9bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw6-f9bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:palette-swatch-variant" {...props}></Icon>
