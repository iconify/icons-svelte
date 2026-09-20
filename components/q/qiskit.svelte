<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scjrk4bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scjrk4bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:qiskit" {...props}></Icon>
