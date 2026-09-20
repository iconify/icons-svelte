<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y13z0jbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y13z0jbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amazoncloudwatch" {...props}></Icon>
