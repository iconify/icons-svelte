<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd7rfbbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd7rfbbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:calculation-1-filled" {...props}></Icon>
