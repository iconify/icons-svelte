<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chpcrjbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chpcrjbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:chart-pie" {...props}></Icon>
