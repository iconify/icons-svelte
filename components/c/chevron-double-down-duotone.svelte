<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd03k58vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zd03k58vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-double-down-duotone" {...props}></Icon>
