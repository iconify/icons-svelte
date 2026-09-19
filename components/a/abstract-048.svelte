<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp6-7xz1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mp6-7xz1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-048" {...props}></Icon>
