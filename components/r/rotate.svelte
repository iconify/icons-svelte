<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-w5woboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-w5woboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rotate" {...props}></Icon>
