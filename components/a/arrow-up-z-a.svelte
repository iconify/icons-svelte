<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-f-uz-ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-f-uz-ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-up-z-a" {...props}></Icon>
