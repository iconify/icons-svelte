<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut1a-rj1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ut1a-rj1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-filament-alt" {...props}></Icon>
