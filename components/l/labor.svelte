<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htn04kbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htn04kbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:labor" {...props}></Icon>
