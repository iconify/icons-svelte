<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhytieb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhytieb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-horizontal-distribute-center" {...props}></Icon>
