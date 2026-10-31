<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ills4eu0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ills4eu0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:code" {...props}></Icon>
