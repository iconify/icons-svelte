<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nddma2zxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nddma2zxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:book-solid" {...props}></Icon>
