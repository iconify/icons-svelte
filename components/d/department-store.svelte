<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igct2tclx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igct2tclx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:department-store" {...props}></Icon>
