<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ieveh1t1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ieveh1t1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:domains" {...props}></Icon>
