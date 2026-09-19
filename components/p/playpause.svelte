<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9p8olbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="b9p8olbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:playpause" {...props}></Icon>
