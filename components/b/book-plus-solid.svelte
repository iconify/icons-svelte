<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm8bkbbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm8bkbbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:book-plus-solid" {...props}></Icon>
