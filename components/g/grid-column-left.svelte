<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttk0ucc9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttk0ucc9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-column-left" {...props}></Icon>
