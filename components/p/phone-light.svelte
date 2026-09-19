<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxyqm2j5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxyqm2j5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:phone-light" {...props}></Icon>
