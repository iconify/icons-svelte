<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5-240xqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5-240xqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chevrons-up" {...props}></Icon>
