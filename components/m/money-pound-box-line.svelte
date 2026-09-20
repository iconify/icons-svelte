<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chcamsw5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chcamsw5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:money-pound-box-line" {...props}></Icon>
