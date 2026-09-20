<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzl-r7bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzl-r7bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:medium-line" {...props}></Icon>
