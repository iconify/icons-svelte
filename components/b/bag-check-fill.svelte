<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyu3_qfzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pyu3_qfzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bag-check-fill" {...props}></Icon>
