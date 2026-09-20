<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoz0d_b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uoz0d_b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:float-none" {...props}></Icon>
