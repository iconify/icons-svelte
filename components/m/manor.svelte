<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l52m8gbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l52m8gbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:manor" {...props}></Icon>
