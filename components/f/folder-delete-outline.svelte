<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0tan9jgf.css';
import '../../css/f/f_tab8g_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0tan9jgf"/><path clip-rule="evenodd" class="f_tab8g_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:folder-delete-outline" {...props}></Icon>
