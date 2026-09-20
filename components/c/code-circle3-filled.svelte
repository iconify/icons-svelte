<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw_vlx9eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw_vlx9eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:code-circle3-filled" {...props}></Icon>
