<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_1b6abit.css';
import '../../css/z/ztdsiac1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_1b6abit"/><path class="ztdsiac1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:owl" {...props}></Icon>
