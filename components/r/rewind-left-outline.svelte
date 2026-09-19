<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh9o9hbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh9o9hbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:rewind-left-outline" {...props}></Icon>
