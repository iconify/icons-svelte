<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq39-hb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq39-hb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:confirmations-6-outline" {...props}></Icon>
