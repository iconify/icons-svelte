<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzf88t2wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzf88t2wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:code-brackets" {...props}></Icon>
