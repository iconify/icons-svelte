<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqlyu657b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hqlyu657b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flood" {...props}></Icon>
