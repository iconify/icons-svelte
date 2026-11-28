<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewhk_6ffn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewhk_6ffn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bike" {...props}></Icon>
