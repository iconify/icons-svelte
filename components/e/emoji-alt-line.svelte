<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk_56sbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk_56sbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:emoji-alt-line" {...props}></Icon>
