<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm4hm_17s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm4hm_17s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:list-indent-decrease" {...props}></Icon>
