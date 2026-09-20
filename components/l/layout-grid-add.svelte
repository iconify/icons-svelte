<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_e47cbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_e47cbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-grid-add" {...props}></Icon>
