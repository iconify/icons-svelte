<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eic0nhb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eic0nhb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ember-shot" {...props}></Icon>
