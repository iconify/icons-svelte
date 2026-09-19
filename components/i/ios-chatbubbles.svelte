<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioyychypw.css';
import '../../css/a/ahrqr1byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ioyychypw"/><path class="ahrqr1byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-chatbubbles" {...props}></Icon>
