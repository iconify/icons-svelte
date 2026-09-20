<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzot9ebny.css';
import '../../css/e/eexszhbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jzot9ebny"/><path class="eexszhbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chitchatter" {...props}></Icon>
