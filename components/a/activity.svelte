<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9sh5i22h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="j9sh5i22h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:activity" {...props}></Icon>
