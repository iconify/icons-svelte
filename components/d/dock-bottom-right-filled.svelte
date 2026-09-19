<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh0iujzym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh0iujzym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-bottom-right-filled" {...props}></Icon>
