<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy95fsbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy95fsbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pen-nib-line" {...props}></Icon>
