<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb7mribhr.css';
import '../../css/g/gt_-n5bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hb7mribhr"/><path class="gt_-n5bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:movie-cinema-watch-bold" {...props}></Icon>
