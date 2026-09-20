<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh-tc02bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh-tc02bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-slack" {...props}></Icon>
