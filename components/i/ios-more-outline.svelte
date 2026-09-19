<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwyxrkbgu.css';
import '../../css/e/ec9sckbjq.css';
import '../../css/g/grxa6ebnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cwyxrkbgu"/><path class="ec9sckbjq"/><path class="grxa6ebnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-more-outline" {...props}></Icon>
