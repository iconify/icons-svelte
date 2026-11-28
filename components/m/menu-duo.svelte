<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak2xm7a5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ak2xm7a5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:menu-duo" {...props}></Icon>
