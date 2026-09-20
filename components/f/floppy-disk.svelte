<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr8we86-j.css';
import '../../css/r/rpkhy_b3u.css';
import '../../css/h/hsmq3ob6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr8we86-j"/><path class="rpkhy_b3u"/><path class="hsmq3ob6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:floppy-disk" {...props}></Icon>
