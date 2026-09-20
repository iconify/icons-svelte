<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um9xjdh3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um9xjdh3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-arrow-left" {...props}></Icon>
