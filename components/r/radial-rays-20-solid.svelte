<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4aqn1b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="f4aqn1b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:radial-rays-20-solid" {...props}></Icon>
