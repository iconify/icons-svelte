<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbmqt9b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbmqt9b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:phone-incoming" {...props}></Icon>
