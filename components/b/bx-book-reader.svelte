<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oor5lmtnx.css';
import '../../css/v/v_ha0xbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oor5lmtnx"/><circle class="v_ha0xbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-book-reader" {...props}></Icon>
