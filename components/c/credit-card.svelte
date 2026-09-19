<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xllkmob9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xllkmob9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:credit-card" {...props}></Icon>
