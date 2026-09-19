<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu6oghb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wu6oghb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dice-twenty-faces-one" {...props}></Icon>
