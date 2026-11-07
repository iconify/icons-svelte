<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u90m3kb-a.css';
import '../../css/p/pzmtr-buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u90m3kb-a"/><path clip-rule="evenodd" class="pzmtr-buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-down-outline" {...props}></Icon>
