<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd0c7ccwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rd0c7ccwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:hashtag-20-solid" {...props}></Icon>
