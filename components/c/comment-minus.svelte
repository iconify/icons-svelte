<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os_7itbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="os_7itbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-minus" {...props}></Icon>
