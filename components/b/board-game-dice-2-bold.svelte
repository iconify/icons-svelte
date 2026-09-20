<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcaebbcnz.css';
import '../../css/n/n2luvz5yf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcaebbcnz"/><path class="n2luvz5yf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:board-game-dice-2-bold" {...props}></Icon>
