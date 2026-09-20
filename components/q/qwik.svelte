<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw27ubbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hw27ubbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:qwik" {...props}></Icon>
