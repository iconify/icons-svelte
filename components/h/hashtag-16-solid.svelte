<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw31vrbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zw31vrbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:hashtag-16-solid" {...props}></Icon>
