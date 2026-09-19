<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elu5rbx0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="elu5rbx0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:perspective-dice-three" {...props}></Icon>
