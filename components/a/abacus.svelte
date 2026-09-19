<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkvqyhbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkvqyhbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:abacus" {...props}></Icon>
