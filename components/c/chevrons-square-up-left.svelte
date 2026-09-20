<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy1m_pe3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="zy1m_pe3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-square-up-left" {...props}></Icon>
