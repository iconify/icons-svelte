<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvnl4tf6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvnl4tf6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-pull-request-arrow" {...props}></Icon>
