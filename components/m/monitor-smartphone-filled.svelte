<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyikwltxa.css';
import '../../css/v/vfl-qubxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyikwltxa"/><path class="vfl-qubxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-smartphone-filled" {...props}></Icon>
