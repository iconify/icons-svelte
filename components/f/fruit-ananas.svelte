<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/texu0db1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="texu0db1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fruit-ananas" {...props}></Icon>
