<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsfyxcbeq.css';
import '../../css/f/fjqlh3bxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsfyxcbeq"/><path class="fjqlh3bxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:coin" {...props}></Icon>
