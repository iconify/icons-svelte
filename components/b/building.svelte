<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyko8xbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qyko8xbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:building" {...props}></Icon>
