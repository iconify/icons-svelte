<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4gn4qb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4gn4qb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-right-bulk-round" {...props}></Icon>
