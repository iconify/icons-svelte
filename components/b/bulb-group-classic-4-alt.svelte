<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcq0-gbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcq0-gbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-classic-4-alt" {...props}></Icon>
