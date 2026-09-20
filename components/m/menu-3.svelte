<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c41m9pbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c41m9pbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:menu-3" {...props}></Icon>
