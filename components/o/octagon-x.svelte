<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3xt0hzge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3xt0hzge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:octagon-x" {...props}></Icon>
