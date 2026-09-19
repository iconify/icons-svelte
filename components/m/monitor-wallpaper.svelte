<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_nerh3_q.css';
import '../../css/r/rdl-cintb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_nerh3_q"/><path class="rdl-cintb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:monitor-wallpaper" {...props}></Icon>
