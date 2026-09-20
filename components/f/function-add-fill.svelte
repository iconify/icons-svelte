<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-lciu5bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-lciu5bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:function-add-fill" {...props}></Icon>
