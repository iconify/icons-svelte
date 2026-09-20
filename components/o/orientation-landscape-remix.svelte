<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpzkk_byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cpzkk_byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:orientation-landscape-remix" {...props}></Icon>
