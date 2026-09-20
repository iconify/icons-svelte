<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx2u-p4hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gx2u-p4hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bug-2-fill" {...props}></Icon>
