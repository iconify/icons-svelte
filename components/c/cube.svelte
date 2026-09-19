<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq-i9lbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1007};
const content = `<path class="aq-i9lbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cube" {...props}></Icon>
