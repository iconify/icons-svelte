<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1verfsgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w1verfsgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cc-16-solid" {...props}></Icon>
