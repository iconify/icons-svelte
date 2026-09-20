<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m30tcab1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m30tcab1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pandas" {...props}></Icon>
