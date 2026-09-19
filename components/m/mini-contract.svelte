<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzyta9bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xzyta9bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:mini-contract" {...props}></Icon>
