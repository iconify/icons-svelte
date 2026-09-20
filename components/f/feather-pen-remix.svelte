<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6v13pvko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h6v13pvko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:feather-pen-remix" {...props}></Icon>
