<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0d1-7n1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0d1-7n1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:message-square-diff" {...props}></Icon>
