<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw86z0bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="nw86z0bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevron-circle-left-f" {...props}></Icon>
