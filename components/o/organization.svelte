<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9m5rle_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v9m5rle_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:organization" {...props}></Icon>
