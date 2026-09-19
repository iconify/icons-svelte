<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opee3bbzg.css';
import '../../css/k/ko-zgkb5p.css';
import '../../css/q/q044p6bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opee3bbzg"/><rect class="ko-zgkb5p"/><rect class="q044p6bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:menu-arrow-fill" {...props}></Icon>
