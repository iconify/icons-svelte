<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm1-0cdzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm1-0cdzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:array" {...props}></Icon>
