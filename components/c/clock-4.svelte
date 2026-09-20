<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8mb6096f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8mb6096f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-4" {...props}></Icon>
