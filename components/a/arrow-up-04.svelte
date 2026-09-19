<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbg6fibnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbg6fibnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-up-04" {...props}></Icon>
