<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjn8q6b8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vjn8q6b8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:knee-bandage" {...props}></Icon>
