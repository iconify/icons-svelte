<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgo5q3yca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wgo5q3yca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lock-keyhole-filled" {...props}></Icon>
