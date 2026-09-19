<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axrzqh94a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="axrzqh94a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paper-bomb" {...props}></Icon>
