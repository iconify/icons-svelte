<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3uw17b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3uw17b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:life-saver-solid" {...props}></Icon>
