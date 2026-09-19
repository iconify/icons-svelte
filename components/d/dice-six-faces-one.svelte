<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvunxq2rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zvunxq2rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dice-six-faces-one" {...props}></Icon>
