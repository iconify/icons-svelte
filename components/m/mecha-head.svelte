<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjoe70b5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yjoe70b5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mecha-head" {...props}></Icon>
