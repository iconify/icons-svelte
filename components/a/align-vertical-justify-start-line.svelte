<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh4k0b5ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh4k0b5ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-vertical-justify-start-line" {...props}></Icon>
