<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3lnxtb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3lnxtb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:coderabbit" {...props}></Icon>
