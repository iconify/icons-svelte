<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a12ng2blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a12ng2blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bow-arrow" {...props}></Icon>
