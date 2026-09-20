<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjc_0ibxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjc_0ibxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chevron-right" {...props}></Icon>
