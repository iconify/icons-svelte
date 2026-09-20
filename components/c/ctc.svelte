<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4_6otcrb.css';
import '../../css/s/sy_8ez57r.css';
import '../../css/w/wji-c-ehd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4_6otcrb"/><path class="sy_8ez57r"/><path class="wji-c-ehd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ctc" {...props}></Icon>
