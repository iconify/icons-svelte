<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6rou6sao.css';
import '../../css/y/yismpnbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6rou6sao"/><path class="yismpnbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:database-plus-filled" {...props}></Icon>
