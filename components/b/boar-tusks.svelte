<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx7h1gakz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sx7h1gakz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:boar-tusks" {...props}></Icon>
