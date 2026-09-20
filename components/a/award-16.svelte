<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4npesb2t.css';
import '../../css/c/c6fjxyvsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w4npesb2t"/><path clip-rule="evenodd" class="c6fjxyvsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:award-16" {...props}></Icon>
