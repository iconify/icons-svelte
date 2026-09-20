<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqdl0oujt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yqdl0oujt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:home-1-remix" {...props}></Icon>
