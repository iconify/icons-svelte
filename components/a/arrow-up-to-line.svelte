<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxk16vb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxk16vb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-to-line" {...props}></Icon>
