<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-uunxc6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-uunxc6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paint-roller-round" {...props}></Icon>
