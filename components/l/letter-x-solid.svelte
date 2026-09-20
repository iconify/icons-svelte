<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1lkljlcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1lkljlcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-x-solid" {...props}></Icon>
