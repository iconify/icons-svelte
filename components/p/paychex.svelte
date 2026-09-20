<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic4oz4bwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic4oz4bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:paychex" {...props}></Icon>
