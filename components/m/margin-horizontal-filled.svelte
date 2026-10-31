<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lud6hzb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lud6hzb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:margin-horizontal-filled" {...props}></Icon>
