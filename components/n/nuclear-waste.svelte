<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_z6dqb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v_z6dqb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nuclear-waste" {...props}></Icon>
