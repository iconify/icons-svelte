<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dua799j_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7,"top":-7};
const content = `<path class="dua799j_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevron-down-right" {...props}></Icon>
