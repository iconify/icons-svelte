<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hskyx7mww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hskyx7mww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bear-face" {...props}></Icon>
