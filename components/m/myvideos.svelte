<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3tby64at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":896};
const content = `<path class="v3tby64at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:myvideos" {...props}></Icon>
