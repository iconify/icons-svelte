<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm6notbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm6notbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:check-unread-03" {...props}></Icon>
