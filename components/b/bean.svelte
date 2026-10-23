<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laa1tab1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="laa1tab1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bean" {...props}></Icon>
