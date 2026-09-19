<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8tf56bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h8tf56bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:h2o" {...props}></Icon>
