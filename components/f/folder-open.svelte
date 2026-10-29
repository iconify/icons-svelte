<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwd0xy2he.css';
import '../../css/u/u8e_e0bbm.css';
import '../../css/i/i_7whfb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwd0xy2he"/><path class="u8e_e0bbm"/><path class="i_7whfb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:folder-open" {...props}></Icon>
