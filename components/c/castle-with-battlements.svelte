<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zie-95bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zie-95bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:castle-with-battlements" {...props}></Icon>
