<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utfj6q1tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utfj6q1tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-alert-solid" {...props}></Icon>
