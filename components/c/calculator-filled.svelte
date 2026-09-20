<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y32nol_wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y32nol_wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:calculator-filled" {...props}></Icon>
