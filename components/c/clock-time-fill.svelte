<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh5y2ublw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh5y2ublw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-time-fill" {...props}></Icon>
