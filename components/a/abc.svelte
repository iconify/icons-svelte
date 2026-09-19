<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1j2pacjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1j2pacjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:abc" {...props}></Icon>
