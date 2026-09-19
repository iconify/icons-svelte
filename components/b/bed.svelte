<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwlh1-3tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwlh1-3tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bed" {...props}></Icon>
