<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s37ojkbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s37ojkbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:croc-jaws" {...props}></Icon>
