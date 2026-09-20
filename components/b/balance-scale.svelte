<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcekv60qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcekv60qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:balance-scale" {...props}></Icon>
