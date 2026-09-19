<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx_pg9buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx_pg9buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:battery-0" {...props}></Icon>
