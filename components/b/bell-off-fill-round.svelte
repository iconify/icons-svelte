<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c56ar3k9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c56ar3k9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bell-off-fill-round" {...props}></Icon>
