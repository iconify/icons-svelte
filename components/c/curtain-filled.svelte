<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds42oz0-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds42oz0-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:curtain-filled" {...props}></Icon>
