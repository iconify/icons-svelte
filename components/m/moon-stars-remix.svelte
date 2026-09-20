<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jquahdb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jquahdb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:moon-stars-remix" {...props}></Icon>
