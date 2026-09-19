<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eald8w6bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eald8w6bs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:connectivity-lan-filled" {...props}></Icon>
