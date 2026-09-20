<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqod50btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqod50btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-2-fill" {...props}></Icon>
