<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk3fodb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="tk3fodb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:gmail" {...props}></Icon>
