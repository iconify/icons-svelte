<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwqwepbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwqwepbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:network-off-fill" {...props}></Icon>
