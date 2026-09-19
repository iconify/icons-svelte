<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyfjiwbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="yyfjiwbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:creative-commons-sa" {...props}></Icon>
