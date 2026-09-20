<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug3bg7b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug3bg7b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:boxing-fill" {...props}></Icon>
