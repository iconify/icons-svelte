<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvdow2bek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvdow2bek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:maximize-solid" {...props}></Icon>
