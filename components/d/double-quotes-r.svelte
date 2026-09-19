<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4sbvbb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4sbvbb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:double-quotes-r" {...props}></Icon>
