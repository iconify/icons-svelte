<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udfnkbb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1026};
const content = `<path class="udfnkbb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:flower" {...props}></Icon>
