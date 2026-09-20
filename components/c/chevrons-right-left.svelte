<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxunf795o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxunf795o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chevrons-right-left" {...props}></Icon>
