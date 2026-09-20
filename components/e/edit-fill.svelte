<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmlrazf5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmlrazf5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:edit-fill" {...props}></Icon>
