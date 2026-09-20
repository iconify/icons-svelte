<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ric0ypn-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ric0ypn-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:anycubic" {...props}></Icon>
