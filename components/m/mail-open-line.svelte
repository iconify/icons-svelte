<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if2x6zcnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if2x6zcnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-open-line" {...props}></Icon>
