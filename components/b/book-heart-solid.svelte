<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw5equbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw5equbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:book-heart-solid" {...props}></Icon>
