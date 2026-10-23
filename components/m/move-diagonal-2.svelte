<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab6t1wbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab6t1wbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:move-diagonal-2" {...props}></Icon>
