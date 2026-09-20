<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q74bkpbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q74bkpbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:city-6-filled" {...props}></Icon>
