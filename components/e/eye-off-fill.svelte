<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6wz8cb3t.css';
import '../../css/o/owu91ypwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="t6wz8cb3t"/><path class="owu91ypwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:eye-off-fill" {...props}></Icon>
