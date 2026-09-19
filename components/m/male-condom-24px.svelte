<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d41wx1b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d41wx1b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:male-condom-24px" {...props}></Icon>
