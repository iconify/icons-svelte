<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma5rg2bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1132,"height":626};
const content = `<path class="ma5rg2bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:heteml" {...props}></Icon>
