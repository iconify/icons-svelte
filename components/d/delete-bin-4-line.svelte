<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yohi3qbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yohi3qbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:delete-bin-4-line" {...props}></Icon>
