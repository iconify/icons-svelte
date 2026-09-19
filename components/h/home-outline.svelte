<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh1cy0bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh1cy0bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:home-outline" {...props}></Icon>
