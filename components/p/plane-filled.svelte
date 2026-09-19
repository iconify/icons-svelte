<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viun7ub0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="viun7ub0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:plane-filled" {...props}></Icon>
