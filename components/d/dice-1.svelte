<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9d0y6bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9d0y6bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:dice-1" {...props}></Icon>
