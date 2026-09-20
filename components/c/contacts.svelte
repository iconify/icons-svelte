<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfikmeb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfikmeb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:contacts" {...props}></Icon>
