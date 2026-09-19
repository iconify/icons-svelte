<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4lrn5gzp.css';
import '../../css/s/skk-_uu3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x4lrn5gzp"/><path class="skk-_uu3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:gift-sharp" {...props}></Icon>
