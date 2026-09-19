<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-pyd0_-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-pyd0_-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:info" {...props}></Icon>
