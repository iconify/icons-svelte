<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzck_dcet.css';
import '../../css/h/hxm77oqrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="xzck_dcet"/><path class="hxm77oqrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:reference-architecture" {...props}></Icon>
