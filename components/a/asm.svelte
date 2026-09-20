<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5sa_rb5p.css';
import '../../css/h/hn41-unac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5sa_rb5p"/><path class="hn41-unac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:asm" {...props}></Icon>
