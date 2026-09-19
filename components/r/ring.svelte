<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvz-8k5oh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gvz-8k5oh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ring" {...props}></Icon>
