<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb4ghvnyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb4ghvnyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:gitlab" {...props}></Icon>
