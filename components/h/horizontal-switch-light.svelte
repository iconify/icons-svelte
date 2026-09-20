<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmq22nb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmq22nb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:horizontal-switch-light" {...props}></Icon>
