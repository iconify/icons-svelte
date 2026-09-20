<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjsh7bb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjsh7bb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:door-open-fill" {...props}></Icon>
