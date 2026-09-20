<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9ep4jbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="o9ep4jbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:phone-mobile-phone" {...props}></Icon>
