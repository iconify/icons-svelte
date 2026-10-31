<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh88pebit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh88pebit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bee-round" {...props}></Icon>
