<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc3bqvbgb.css';
import '../../css/i/i6107pbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc3bqvbgb"/><path class="i6107pbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-exclamation" {...props}></Icon>
