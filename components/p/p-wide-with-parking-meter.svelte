<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zii5sn5at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zii5sn5at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:p-wide-with-parking-meter" {...props}></Icon>
