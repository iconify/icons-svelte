<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyzz-jbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xyzz-jbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ppe-mask-24px" {...props}></Icon>
