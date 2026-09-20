<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dis9ojbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dis9ojbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:beach-solid" {...props}></Icon>
