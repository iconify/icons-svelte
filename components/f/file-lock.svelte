<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdq7ct5jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdq7ct5jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-lock" {...props}></Icon>
