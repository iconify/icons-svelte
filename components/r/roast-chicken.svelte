<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_f_lgiel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v_f_lgiel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:roast-chicken" {...props}></Icon>
