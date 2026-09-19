<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5rz7fbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o5rz7fbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:beetle-shell" {...props}></Icon>
