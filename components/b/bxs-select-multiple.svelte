<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-_99-bnr.css';
import '../../css/l/l_u7c-bkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-_99-bnr"/><path class="l_u7c-bkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-select-multiple" {...props}></Icon>
