<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bagg5vb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bagg5vb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:observatory" {...props}></Icon>
