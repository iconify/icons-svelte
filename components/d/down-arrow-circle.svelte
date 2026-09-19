<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgo18hbkg.css';
import '../../css/h/hd_yihbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgo18hbkg"/><path class="hd_yihbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:down-arrow-circle" {...props}></Icon>
