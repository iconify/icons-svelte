<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lthfew8ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lthfew8ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:asio-16" {...props}></Icon>
