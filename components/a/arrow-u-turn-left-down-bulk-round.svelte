<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-hffqb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-hffqb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-u-turn-left-down-bulk-round" {...props}></Icon>
