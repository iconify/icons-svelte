<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zujc2wpbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zujc2wpbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:folder-open" {...props}></Icon>
