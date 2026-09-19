<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvkixbcpd.css';
import '../../css/i/io4621_ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lvkixbcpd"/><path class="io4621_ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:connection" {...props}></Icon>
