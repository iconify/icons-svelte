<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut2-xbo2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary ut2-xbo2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-translate-duotone" {...props}></Icon>
