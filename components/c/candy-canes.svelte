<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-cfzxbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x-cfzxbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:candy-canes" {...props}></Icon>
