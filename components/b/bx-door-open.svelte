<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgxd4gqfq.css';
import '../../css/i/iaz7k-bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgxd4gqfq"/><path class="iaz7k-bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-door-open" {...props}></Icon>
