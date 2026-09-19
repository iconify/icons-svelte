<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb45w1b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pb45w1b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:book-open" {...props}></Icon>
