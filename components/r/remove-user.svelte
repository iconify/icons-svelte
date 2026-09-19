<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bva6fdcpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bva6fdcpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:remove-user" {...props}></Icon>
