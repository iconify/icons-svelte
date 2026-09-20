<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxf-a7bbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxf-a7bbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:add-round-light" {...props}></Icon>
