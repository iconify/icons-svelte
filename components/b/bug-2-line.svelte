<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g61do7b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g61do7b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bug-2-line" {...props}></Icon>
