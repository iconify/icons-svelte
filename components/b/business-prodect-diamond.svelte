<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5p02fbjy.css';
import '../../css/p/p_qjcl89l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a5p02fbjy"/><path class="p_qjcl89l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:business-prodect-diamond" {...props}></Icon>
