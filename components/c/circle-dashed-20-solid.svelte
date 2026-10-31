<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilp_1kbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ilp_1kbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:circle-dashed-20-solid" {...props}></Icon>
