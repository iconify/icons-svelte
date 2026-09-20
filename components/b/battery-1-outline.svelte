<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic4bk9nie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ic4bk9nie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:battery-1-outline" {...props}></Icon>
