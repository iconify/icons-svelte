<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1_f-bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc1_f-bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-horiz-fill" {...props}></Icon>
