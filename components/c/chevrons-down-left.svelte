<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef5jcs_rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-5};
const content = `<path class="ef5jcs_rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-down-left" {...props}></Icon>
