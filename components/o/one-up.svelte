<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzun363fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzun363fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:one-up" {...props}></Icon>
