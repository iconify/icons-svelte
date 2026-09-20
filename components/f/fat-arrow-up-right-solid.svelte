<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4doc9bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4doc9bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fat-arrow-up-right-solid" {...props}></Icon>
