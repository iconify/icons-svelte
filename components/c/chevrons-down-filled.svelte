<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7edix8yx.css';
import '../../css/f/f-emzobbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7edix8yx"/><path class="f-emzobbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chevrons-down-filled" {...props}></Icon>
