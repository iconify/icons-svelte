<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fij5dqbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="fij5dqbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:defibrillator-11" {...props}></Icon>
