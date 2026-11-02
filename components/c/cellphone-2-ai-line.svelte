<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-_ho8emr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-_ho8emr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cellphone-2-ai-line" {...props}></Icon>
