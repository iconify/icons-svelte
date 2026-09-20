<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwj_7qynx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zwj_7qynx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:rockrms" {...props}></Icon>
