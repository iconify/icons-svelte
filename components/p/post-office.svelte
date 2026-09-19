<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuuwx2zco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yuuwx2zco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:post-office" {...props}></Icon>
