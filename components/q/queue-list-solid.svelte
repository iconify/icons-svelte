<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjgy0_bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjgy0_bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:queue-list-solid" {...props}></Icon>
