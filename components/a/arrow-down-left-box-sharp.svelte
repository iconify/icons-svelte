<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn3j_6bgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jn3j_6bgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-down-left-box-sharp" {...props}></Icon>
