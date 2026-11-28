<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdfw7y4er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vdfw7y4er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:line-dashed-duotone" {...props}></Icon>
