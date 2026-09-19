<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nunekbcsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nunekbcsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:help-filled" {...props}></Icon>
