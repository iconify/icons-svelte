<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw4q45bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw4q45bxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:barbell-off" {...props}></Icon>
