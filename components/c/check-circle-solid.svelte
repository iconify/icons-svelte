<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwvmuh2tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwvmuh2tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:check-circle-solid" {...props}></Icon>
