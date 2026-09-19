<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlixbin9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlixbin9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:annotation-dots-filled" {...props}></Icon>
