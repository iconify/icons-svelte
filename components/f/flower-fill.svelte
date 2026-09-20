<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-d6zbbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-d6zbbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flower-fill" {...props}></Icon>
