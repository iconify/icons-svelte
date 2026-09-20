<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b18u8acww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="b18u8acww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:notepad" {...props}></Icon>
