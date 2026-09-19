<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuxz6hvqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="yuxz6hvqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:heart-slash-circle" {...props}></Icon>
