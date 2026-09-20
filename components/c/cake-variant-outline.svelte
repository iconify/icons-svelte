<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qert3hfpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qert3hfpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cake-variant-outline" {...props}></Icon>
