<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpy5q3b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-5};
const content = `<path class="tpy5q3b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-right" {...props}></Icon>
