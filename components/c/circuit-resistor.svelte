<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp3_k5mkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kp3_k5mkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circuit-resistor" {...props}></Icon>
