<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad106q2ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ad106q2ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:keyboard-20-solid" {...props}></Icon>
