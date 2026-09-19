<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmc12mo1y.css';
import '../../css/g/g6nhfybzv.css';
import '../../css/c/cyo88nvfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jmc12mo1y"/><path class="g6nhfybzv"/><path class="cyo88nvfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:male" {...props}></Icon>
