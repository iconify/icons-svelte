<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkfnpiber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkfnpiber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-lock-solid" {...props}></Icon>
