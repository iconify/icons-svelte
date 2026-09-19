<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1r8h7bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o1r8h7bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:large-dress" {...props}></Icon>
