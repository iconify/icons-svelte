<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouaz_3bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouaz_3bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:folder-plus-line" {...props}></Icon>
