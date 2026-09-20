<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e709i7b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e709i7b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:diagram-arrow-down-1" {...props}></Icon>
