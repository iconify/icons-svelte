<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxu9710-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wxu9710-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:percent-20-solid" {...props}></Icon>
