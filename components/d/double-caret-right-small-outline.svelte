<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6zw34bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x6zw34bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-right-small-outline" {...props}></Icon>
