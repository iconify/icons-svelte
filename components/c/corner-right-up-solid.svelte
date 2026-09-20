<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm7rx68mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm7rx68mm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:corner-right-up-solid" {...props}></Icon>
