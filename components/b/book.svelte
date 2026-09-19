<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwnpb3bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":560,"height":850};
const content = `<path class="fwnpb3bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:book" {...props}></Icon>
