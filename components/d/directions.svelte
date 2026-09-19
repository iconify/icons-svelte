<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrqt_secr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zrqt_secr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:directions" {...props}></Icon>
