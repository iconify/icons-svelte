<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt85k4fna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt85k4fna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:plus" {...props}></Icon>
