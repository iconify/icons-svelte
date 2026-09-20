<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxbnmhbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xxbnmhbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:behance-outline" {...props}></Icon>
