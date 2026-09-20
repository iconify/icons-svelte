<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw9r7gbbd.css';
import '../../css/u/ull6c1baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw9r7gbbd"/><path class="ull6c1baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-blocked-filled" {...props}></Icon>
