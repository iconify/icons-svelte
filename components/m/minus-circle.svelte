<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zujlznb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zujlznb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:minus-circle" {...props}></Icon>
