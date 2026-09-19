<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irpf0cyiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irpf0cyiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:beaker" {...props}></Icon>
