<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr3e8ih8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr3e8ih8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-right-md" {...props}></Icon>
