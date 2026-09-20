<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4ba7qyjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4ba7qyjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:align-bottom" {...props}></Icon>
