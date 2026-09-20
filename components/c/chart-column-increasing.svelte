<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmo_n7n5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmo_n7n5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-column-increasing" {...props}></Icon>
