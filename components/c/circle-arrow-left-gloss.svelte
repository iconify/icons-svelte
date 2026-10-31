<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfvnjqbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfvnjqbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-arrow-left-gloss" {...props}></Icon>
