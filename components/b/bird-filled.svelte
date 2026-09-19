<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wacvlc65l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wacvlc65l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bird-filled" {...props}></Icon>
