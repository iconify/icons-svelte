<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahtvzdbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahtvzdbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-down-circle-filled" {...props}></Icon>
