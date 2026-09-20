<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz2f1mbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz2f1mbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:linkedin-line" {...props}></Icon>
