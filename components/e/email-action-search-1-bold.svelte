<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbx4p_6nb.css';
import '../../css/l/l4ej3fvuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbx4p_6nb"/><path class="l4ej3fvuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:email-action-search-1-bold" {...props}></Icon>
