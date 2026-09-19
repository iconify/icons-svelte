<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgfg_vrnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgfg_vrnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:calendar-plus" {...props}></Icon>
