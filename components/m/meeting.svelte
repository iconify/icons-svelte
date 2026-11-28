<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4kw_vbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4kw_vbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:meeting" {...props}></Icon>
