<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z65ujlb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z65ujlb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:layout-window-8-remix" {...props}></Icon>
