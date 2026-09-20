<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi1hetygf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi1hetygf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hq-fill" {...props}></Icon>
