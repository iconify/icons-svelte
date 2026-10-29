<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t15hl03kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t15hl03kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:package-x" {...props}></Icon>
