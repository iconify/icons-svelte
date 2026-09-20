<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chlk_vb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chlk_vb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cry-loudly-filled" {...props}></Icon>
