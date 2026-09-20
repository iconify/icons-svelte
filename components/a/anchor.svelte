<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9n1frbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9n1frbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:anchor" {...props}></Icon>
