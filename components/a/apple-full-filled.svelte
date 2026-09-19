<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms7wlk1xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms7wlk1xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:apple-full-filled" {...props}></Icon>
