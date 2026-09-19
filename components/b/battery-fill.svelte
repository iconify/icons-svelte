<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sregglbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sregglbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:battery-fill" {...props}></Icon>
