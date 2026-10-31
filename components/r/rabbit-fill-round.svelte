<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz7rj6bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bz7rj6bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:rabbit-fill-round" {...props}></Icon>
