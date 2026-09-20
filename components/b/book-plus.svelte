<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf-9d60ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf-9d60ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:book-plus" {...props}></Icon>
