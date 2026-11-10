<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az_l_5bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="az_l_5bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bookmark-x-mark-solid" {...props}></Icon>
