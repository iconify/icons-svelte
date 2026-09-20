<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsvz2pfes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wsvz2pfes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chart-outline" {...props}></Icon>
