<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmq1amubh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmq1amubh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:package-sharp" {...props}></Icon>
