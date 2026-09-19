<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyolqcc_l.css';
import '../../css/s/s28o31bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yyolqcc_l"/><path class="s28o31bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-unprotected" {...props}></Icon>
