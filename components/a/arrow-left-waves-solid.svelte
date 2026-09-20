<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8eu9ebpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8eu9ebpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-left-waves-solid" {...props}></Icon>
