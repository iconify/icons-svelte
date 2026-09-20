<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgmse4pkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jgmse4pkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:disney-plus-light" {...props}></Icon>
