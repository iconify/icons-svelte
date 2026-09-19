<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_69m0s2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c_69m0s2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:anvil" {...props}></Icon>
