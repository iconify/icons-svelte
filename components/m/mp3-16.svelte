<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou25alb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ou25alb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:mp3-16" {...props}></Icon>
