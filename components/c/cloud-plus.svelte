<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrqj4fbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrqj4fbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-plus" {...props}></Icon>
