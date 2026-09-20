<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9eirc5vf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9eirc5vf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:razor" {...props}></Icon>
