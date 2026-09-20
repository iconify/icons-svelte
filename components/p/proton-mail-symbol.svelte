<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy-6gvnnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy-6gvnnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:proton-mail-symbol" {...props}></Icon>
