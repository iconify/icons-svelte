<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc9m0jmpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gc9m0jmpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-up-left-square-solid" {...props}></Icon>
