<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz3cmqw6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz3cmqw6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-chevron-down" {...props}></Icon>
