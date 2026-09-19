<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwtt7-lhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwtt7-lhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:menu-grid-o" {...props}></Icon>
