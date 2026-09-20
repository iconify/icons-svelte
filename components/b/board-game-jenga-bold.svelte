<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txz7hobqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txz7hobqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:board-game-jenga-bold" {...props}></Icon>
