<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsyuo0y3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsyuo0y3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrow-up-left" {...props}></Icon>
