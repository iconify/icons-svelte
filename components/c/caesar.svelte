<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_baz8oie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w_baz8oie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:caesar" {...props}></Icon>
