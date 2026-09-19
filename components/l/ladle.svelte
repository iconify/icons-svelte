<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf6b-jb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lf6b-jb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ladle" {...props}></Icon>
