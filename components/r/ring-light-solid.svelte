<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-06ykbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-06ykbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ring-light-solid" {...props}></Icon>
