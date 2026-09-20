<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq80f2hmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kq80f2hmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:heart-with-bolt" {...props}></Icon>
