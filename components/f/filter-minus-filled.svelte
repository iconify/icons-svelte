<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/v/vdds3c.css';
import '../../css/l/l9ncqp.css';
import '../../css/s/so-from-54.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew vdds3c"/><path class="iw1iew l9ncqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:filter-minus-filled" {...props}></Icon>
