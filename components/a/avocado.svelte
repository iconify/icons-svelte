<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjw7bkbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zjw7bkbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:avocado" {...props}></Icon>
