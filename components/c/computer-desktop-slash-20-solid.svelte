<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co8pgjoyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="co8pgjoyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:computer-desktop-slash-20-solid" {...props}></Icon>
