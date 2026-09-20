<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewgzu34ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ewgzu34ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rosterhash-dark" {...props}></Icon>
