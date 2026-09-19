<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb7rgwp0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pb7rgwp0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:archive-box-x-mark" {...props}></Icon>
