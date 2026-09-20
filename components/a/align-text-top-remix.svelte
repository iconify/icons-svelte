<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my3y--76b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="my3y--76b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:align-text-top-remix" {...props}></Icon>
