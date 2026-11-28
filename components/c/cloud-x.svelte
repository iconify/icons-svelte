<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyex3lbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyex3lbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cloud-x" {...props}></Icon>
