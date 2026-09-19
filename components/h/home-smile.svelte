<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhf3-7eiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhf3-7eiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:home-smile" {...props}></Icon>
