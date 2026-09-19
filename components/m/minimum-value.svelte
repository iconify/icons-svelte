<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh-00ibey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dh-00ibey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:minimum-value" {...props}></Icon>
