<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyc6-gqkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vyc6-gqkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:luchador" {...props}></Icon>
