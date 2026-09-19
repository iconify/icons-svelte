<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjsqj1b1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fjsqj1b1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:game-die-small" {...props}></Icon>
