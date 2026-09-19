<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv996kwky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv996kwky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:plane-alt" {...props}></Icon>
