<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exfs0mb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exfs0mb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-z-a" {...props}></Icon>
