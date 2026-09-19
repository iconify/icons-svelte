<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehs20_byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ehs20_byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:connect-contacts" {...props}></Icon>
