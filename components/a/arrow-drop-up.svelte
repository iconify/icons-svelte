<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl891nbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl891nbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arrow-drop-up" {...props}></Icon>
