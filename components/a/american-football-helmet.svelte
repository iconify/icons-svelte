<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t74_h4bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t74_h4bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:american-football-helmet" {...props}></Icon>
