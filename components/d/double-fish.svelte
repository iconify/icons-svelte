<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7aowb5fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l7aowb5fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:double-fish" {...props}></Icon>
