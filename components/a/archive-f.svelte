<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysv-tqb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="ysv-tqb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:archive-f" {...props}></Icon>
