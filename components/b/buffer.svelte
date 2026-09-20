<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjalun17s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjalun17s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:buffer" {...props}></Icon>
