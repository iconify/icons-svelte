<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3obyzj7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3obyzj7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:align-right" {...props}></Icon>
