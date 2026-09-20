<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msx1qubsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msx1qubsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:microphone-filled" {...props}></Icon>
