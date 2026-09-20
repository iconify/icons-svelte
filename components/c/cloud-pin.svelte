<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxvb0bbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxvb0bbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-pin" {...props}></Icon>
