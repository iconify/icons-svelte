<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg2ph0bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg2ph0bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:pen-mark-filled" {...props}></Icon>
