<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r29f78hcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r29f78hcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:roman-numeral-9" {...props}></Icon>
