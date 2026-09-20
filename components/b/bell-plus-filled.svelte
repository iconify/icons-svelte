<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv4-_kbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv4-_kbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-plus-filled" {...props}></Icon>
