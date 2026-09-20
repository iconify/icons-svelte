<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncroei_gj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncroei_gj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:makerbot" {...props}></Icon>
