<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fra7p-djj.css';
import '../../css/t/t_2-m239s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="fra7p-djj"/><path class="t_2-m239s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:european-union" {...props}></Icon>
