<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw9ue2s1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pw9ue2s1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-card" {...props}></Icon>
