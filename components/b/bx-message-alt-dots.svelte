<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0fcgjs6s.css';
import '../../css/c/cg7d2pfom.css';
import '../../css/r/r_d7t_bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0fcgjs6s"/><circle class="cg7d2pfom"/><circle class="r_d7t_bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-message-alt-dots" {...props}></Icon>
