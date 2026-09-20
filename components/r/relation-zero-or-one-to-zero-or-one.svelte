<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-ssqcc4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-ssqcc4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-zero-or-one-to-zero-or-one" {...props}></Icon>
