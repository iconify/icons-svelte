<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8v583a5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8v583a5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:corner-left-down-fill" {...props}></Icon>
