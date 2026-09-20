<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6btrcb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6btrcb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-big-up-left-solid" {...props}></Icon>
