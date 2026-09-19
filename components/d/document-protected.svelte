<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mogbiy72d.css';
import '../../css/y/yyolqcc_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mogbiy72d"/><path class="yyolqcc_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-protected" {...props}></Icon>
