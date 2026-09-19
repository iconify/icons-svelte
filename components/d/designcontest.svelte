<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyxrfty-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":961,"height":1025};
const content = `<path class="yyxrfty-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:designcontest" {...props}></Icon>
