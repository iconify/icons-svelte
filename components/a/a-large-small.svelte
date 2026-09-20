<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq_6aabuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq_6aabuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:a-large-small" {...props}></Icon>
