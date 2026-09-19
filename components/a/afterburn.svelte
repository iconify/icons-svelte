<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag0ety1ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ag0ety1ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:afterburn" {...props}></Icon>
