<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3t19-9ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v3t19-9ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:add-sign-bold" {...props}></Icon>
