<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rch-wrbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rch-wrbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-lock" {...props}></Icon>
