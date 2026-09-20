<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czbzcw-8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czbzcw-8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-down-up" {...props}></Icon>
