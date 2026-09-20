<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsur8-ztq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsur8-ztq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:pasta-bowl-warm-bold" {...props}></Icon>
