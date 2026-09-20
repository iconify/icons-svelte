<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcpq3tb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcpq3tb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-minus" {...props}></Icon>
