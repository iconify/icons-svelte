<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfi6zzj9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfi6zzj9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-watch-alt" {...props}></Icon>
