<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7d6o3kik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7d6o3kik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:double-check-fill" {...props}></Icon>
