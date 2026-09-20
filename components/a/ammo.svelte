<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3zweqbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="m3zweqbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:ammo" {...props}></Icon>
