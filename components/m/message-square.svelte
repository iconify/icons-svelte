<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjkgeh70e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjkgeh70e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square" {...props}></Icon>
