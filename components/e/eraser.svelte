<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk3isu6tj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk3isu6tj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:eraser" {...props}></Icon>
