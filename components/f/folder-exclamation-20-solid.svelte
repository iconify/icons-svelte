<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyvqyt90u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="iyvqyt90u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:folder-exclamation-20-solid" {...props}></Icon>
