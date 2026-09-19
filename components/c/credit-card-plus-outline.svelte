<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvax7ob5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvax7ob5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:credit-card-plus-outline" {...props}></Icon>
