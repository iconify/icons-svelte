<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiozq7bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yiozq7bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:moon-alt" {...props}></Icon>
