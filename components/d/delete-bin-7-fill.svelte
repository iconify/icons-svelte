<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqx0c2-nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqx0c2-nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:delete-bin-7-fill" {...props}></Icon>
