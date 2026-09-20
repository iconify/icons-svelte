<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh8d11bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh8d11bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-up-left-solid" {...props}></Icon>
