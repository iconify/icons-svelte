<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc834ogky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc834ogky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pencil-line" {...props}></Icon>
