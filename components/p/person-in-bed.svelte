<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adqn4c7sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="adqn4c7sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:person-in-bed" {...props}></Icon>
