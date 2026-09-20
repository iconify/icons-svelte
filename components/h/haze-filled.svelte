<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayuyt_49f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ayuyt_49f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:haze-filled" {...props}></Icon>
