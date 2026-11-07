<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_q0ozs9d.css';
import '../../css/i/iddfz9biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o_q0ozs9d"/><path class="iddfz9biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:course-up-bold-duotone" {...props}></Icon>
