<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yru80ibvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yru80ibvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:battery-plus" {...props}></Icon>
