<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb0uyplao.css';
import '../../css/v/volv26bxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bb0uyplao"/><path class="volv26bxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-quote" {...props}></Icon>
