<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amie3nbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="amie3nbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:p90" {...props}></Icon>
