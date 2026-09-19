<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8xfwqbqk.css';
import '../../css/i/i7-t02b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8xfwqbqk"/><path class="i7-t02b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:8-ball-filled" {...props}></Icon>
