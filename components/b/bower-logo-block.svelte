<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrd3bnp0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rrd3bnp0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bower-logo-block" {...props}></Icon>
