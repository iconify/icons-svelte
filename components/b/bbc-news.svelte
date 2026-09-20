<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qik18r02u.css';
import '../../css/j/jxi1ylssz.css';
import '../../css/p/p3j752dkn.css';
import '../../css/s/s01r7qvek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":300};
const content = `<path class="qik18r02u"/><path class="jxi1ylssz"/><path class="p3j752dkn"/><path class="s01r7qvek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bbc-news" {...props}></Icon>
