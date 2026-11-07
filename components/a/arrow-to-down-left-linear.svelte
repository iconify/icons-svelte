<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooub8eoja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ooub8eoja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-to-down-left-linear" {...props}></Icon>
