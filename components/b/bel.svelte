<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rta1vqbep.css';
import '../../css/e/eldc1fran.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rta1vqbep"/><path class="eldc1fran"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bel" {...props}></Icon>
