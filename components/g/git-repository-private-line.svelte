<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so8-4ab0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so8-4ab0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:git-repository-private-line" {...props}></Icon>
