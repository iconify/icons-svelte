<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi8elsf9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xi8elsf9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:plug" {...props}></Icon>
