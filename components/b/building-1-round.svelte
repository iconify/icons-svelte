<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b70fpkbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b70fpkbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-1-round" {...props}></Icon>
