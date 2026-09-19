<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt6oaq06m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qt6oaq06m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:batteries" {...props}></Icon>
