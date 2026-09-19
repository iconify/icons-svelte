<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re6rncfpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="re6rncfpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:figurehead" {...props}></Icon>
