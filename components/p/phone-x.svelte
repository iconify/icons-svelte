<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w15nws47s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w15nws47s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:phone-x" {...props}></Icon>
