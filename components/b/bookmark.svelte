<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg8ox3wza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yg8ox3wza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:bookmark" {...props}></Icon>
