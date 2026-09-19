<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5b42eb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h5b42eb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:inverted-dice-5" {...props}></Icon>
