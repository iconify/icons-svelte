<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miz1qxb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="miz1qxb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:capitol" {...props}></Icon>
