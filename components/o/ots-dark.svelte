<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b__0lfg-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b__0lfg-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ots-dark" {...props}></Icon>
