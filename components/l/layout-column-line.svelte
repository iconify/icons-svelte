<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuptu_q2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuptu_q2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-column-line" {...props}></Icon>
