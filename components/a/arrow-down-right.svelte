<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thz528qjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thz528qjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-down-right" {...props}></Icon>
