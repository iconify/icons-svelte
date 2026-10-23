<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr7obeqxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr7obeqxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:list-chevrons-up-down" {...props}></Icon>
