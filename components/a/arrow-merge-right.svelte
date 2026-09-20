<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn9uko5kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn9uko5kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-merge-right" {...props}></Icon>
