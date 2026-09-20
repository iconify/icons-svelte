<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz__jgbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz__jgbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circuit-cell-plus" {...props}></Icon>
