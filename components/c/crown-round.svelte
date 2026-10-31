<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1b4pqe1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1b4pqe1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:crown-round" {...props}></Icon>
