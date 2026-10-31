<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjhj6ccbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vjhj6ccbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:computer-laptop-20-solid" {...props}></Icon>
