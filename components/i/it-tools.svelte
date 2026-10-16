<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re9t7ccrz.css';
import '../../css/x/xd65xdbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":726,"height":726};
const content = `<path class="re9t7ccrz"/><path class="xd65xdbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:it-tools" {...props}></Icon>
