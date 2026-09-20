<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysjm1rbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysjm1rbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:delete-bin-2-line" {...props}></Icon>
