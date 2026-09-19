<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyf2ujb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyf2ujb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-muscari" {...props}></Icon>
