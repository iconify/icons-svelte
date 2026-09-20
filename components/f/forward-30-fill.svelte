<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdxad1bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdxad1bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:forward-30-fill" {...props}></Icon>
