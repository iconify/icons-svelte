<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycoy9kbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycoy9kbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:database-minus" {...props}></Icon>
