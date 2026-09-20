<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uynm4kapm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uynm4kapm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:lightning-bolt" {...props}></Icon>
