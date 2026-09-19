<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fynt03bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fynt03bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:go-to-next-cell-outline" {...props}></Icon>
