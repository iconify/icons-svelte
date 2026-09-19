<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aftt2ekiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aftt2ekiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ecowitt" {...props}></Icon>
