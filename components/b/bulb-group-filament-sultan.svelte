<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqet__b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqet__b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-filament-sultan" {...props}></Icon>
