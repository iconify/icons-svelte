<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaj0pkbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1179,"height":1000};
const content = `<path class="jaj0pkbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:comment-alt" {...props}></Icon>
