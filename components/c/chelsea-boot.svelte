<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdum019nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bdum019nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chelsea-boot" {...props}></Icon>
