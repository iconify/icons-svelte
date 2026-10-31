<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqpdxihwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqpdxihwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:dumbbell-fill-round" {...props}></Icon>
