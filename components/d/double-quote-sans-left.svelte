<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b90yzlbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b90yzlbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:double-quote-sans-left" {...props}></Icon>
