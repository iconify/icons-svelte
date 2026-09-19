<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifduj-p8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifduj-p8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:minus-circle-filled" {...props}></Icon>
