<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcgfedc7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcgfedc7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:convertshape2-filled" {...props}></Icon>
