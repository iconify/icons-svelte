<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zieuvnddo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zieuvnddo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:creative-commons-filled" {...props}></Icon>
