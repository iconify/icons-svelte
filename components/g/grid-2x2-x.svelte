<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxf16j32g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxf16j32g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:grid-2x2-x" {...props}></Icon>
