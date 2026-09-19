<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz-3-qpad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zz-3-qpad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nurse-female" {...props}></Icon>
