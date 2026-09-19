<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znh_s8bvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znh_s8bvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:globe" {...props}></Icon>
