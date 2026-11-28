<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-fc0ocqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary x-fc0ocqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-up-duotone" {...props}></Icon>
