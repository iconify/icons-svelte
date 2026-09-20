<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbmck-b3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qbmck-b3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:redwoodjs-outline" {...props}></Icon>
