<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzaaavbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzaaavbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:attach-fill" {...props}></Icon>
