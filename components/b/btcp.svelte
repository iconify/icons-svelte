<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6g_i0b7t.css';
import '../../css/t/tt34x7bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6g_i0b7t"/><path class="tt34x7bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:btcp" {...props}></Icon>
