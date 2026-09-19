<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en_bw8biv.css';
import '../../css/c/cioxv2q3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="en_bw8biv"/><path clip-rule="evenodd" class="cioxv2q3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:creative-commons-noderivs" {...props}></Icon>
