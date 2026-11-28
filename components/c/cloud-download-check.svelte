<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6ag-dbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6ag-dbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cloud-download-check" {...props}></Icon>
