<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py6kwddky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py6kwddky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:git-fork-fill" {...props}></Icon>
