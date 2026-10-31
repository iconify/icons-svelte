<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf6_acwvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="sf6_acwvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:paint-brush-slash-20-solid" {...props}></Icon>
