<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oydwh62tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oydwh62tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:notion-filled" {...props}></Icon>
