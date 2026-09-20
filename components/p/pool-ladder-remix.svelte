<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze53kprie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ze53kprie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pool-ladder-remix" {...props}></Icon>
