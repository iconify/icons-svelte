<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov_ok3q0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov_ok3q0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dot-grid-fill" {...props}></Icon>
