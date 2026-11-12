<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsfg69j0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsfg69j0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-key" {...props}></Icon>
