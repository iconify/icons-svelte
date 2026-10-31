<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im0xc24va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="im0xc24va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chevron-left-right-20-solid" {...props}></Icon>
