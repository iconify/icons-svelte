<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geig7zbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="geig7zbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pincers" {...props}></Icon>
