<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-f--jfeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-f--jfeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:download-alt" {...props}></Icon>
