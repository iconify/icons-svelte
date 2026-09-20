<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr1ukwbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zr1ukwbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:code-analysis-solid" {...props}></Icon>
