<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt6x9_b7p.css';
import '../../css/i/iu35e1xme.css';
import '../../css/w/wa-7pugao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt6x9_b7p"/><circle class="iu35e1xme"/><path class="wa-7pugao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:exclamation-octagon" {...props}></Icon>
