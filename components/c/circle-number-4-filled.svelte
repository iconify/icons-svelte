<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb1gmnbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb1gmnbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-number-4-filled" {...props}></Icon>
