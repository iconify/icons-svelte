<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbd9j875s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbd9j875s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:rocket-check" {...props}></Icon>
