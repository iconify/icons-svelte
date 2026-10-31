<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7is6ubrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7is6ubrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clock-2-fill-round" {...props}></Icon>
