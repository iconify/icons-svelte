<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxh9hzbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxh9hzbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:refresh-ccw-alt" {...props}></Icon>
