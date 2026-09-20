<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-1fa5hld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-1fa5hld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-heart" {...props}></Icon>
