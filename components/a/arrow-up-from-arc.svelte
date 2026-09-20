<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp53ru0ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vp53ru0ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-up-from-arc" {...props}></Icon>
