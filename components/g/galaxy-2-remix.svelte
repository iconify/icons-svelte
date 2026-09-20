<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx12uhtbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mx12uhtbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:galaxy-2-remix" {...props}></Icon>
