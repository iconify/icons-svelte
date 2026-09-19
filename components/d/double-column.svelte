<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg9io8bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hg9io8bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:double-column" {...props}></Icon>
