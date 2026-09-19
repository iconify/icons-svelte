<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfvn8jbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lfvn8jbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:oppression" {...props}></Icon>
