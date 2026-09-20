<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uax31b8tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uax31b8tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chart-radial" {...props}></Icon>
