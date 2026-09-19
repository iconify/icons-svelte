<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz1m15bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kz1m15bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:duco-1" {...props}></Icon>
