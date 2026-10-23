<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmp864_0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmp864_0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cloud-check" {...props}></Icon>
