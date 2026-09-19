<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkiql8hbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kkiql8hbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-089" {...props}></Icon>
