<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2keqxlad.css';
import '../../css/c/cbeuwxbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2keqxlad"/><path class="cbeuwxbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:room" {...props}></Icon>
