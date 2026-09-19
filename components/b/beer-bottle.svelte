<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn0htrb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kn0htrb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:beer-bottle" {...props}></Icon>
