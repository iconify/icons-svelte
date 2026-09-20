<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rspl2bbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rspl2bbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:alarm-clock" {...props}></Icon>
