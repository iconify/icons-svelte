<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyj8jf1aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="fyj8jf1aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:alien-solid" {...props}></Icon>
