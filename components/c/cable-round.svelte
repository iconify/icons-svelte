<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4v7tl5oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4v7tl5oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cable-round" {...props}></Icon>
