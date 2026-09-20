<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zka2d_b1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zka2d_b1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:driver2" {...props}></Icon>
