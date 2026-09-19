<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hugphw97q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hugphw97q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:mug-saucer-outline" {...props}></Icon>
