<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oenq7gbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oenq7gbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ram-profile" {...props}></Icon>
