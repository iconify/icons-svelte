<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yarw-nzsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yarw-nzsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rainbow-line" {...props}></Icon>
