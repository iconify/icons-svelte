<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxe-7xbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xxe-7xbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:buildings-bold" {...props}></Icon>
