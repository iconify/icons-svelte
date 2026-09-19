<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6n9ygbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6n9ygbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-filament-alt" {...props}></Icon>
