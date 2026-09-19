<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eebk2rb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eebk2rb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:kite" {...props}></Icon>
