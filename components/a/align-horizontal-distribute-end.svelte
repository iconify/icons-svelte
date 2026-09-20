<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2txpnd4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2txpnd4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-horizontal-distribute-end" {...props}></Icon>
