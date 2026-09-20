<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aets0ymif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aets0ymif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:badge-percent" {...props}></Icon>
