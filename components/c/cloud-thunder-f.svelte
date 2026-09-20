<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzm7-0bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="yzm7-0bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:cloud-thunder-f" {...props}></Icon>
