<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m30rb2h_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m30rb2h_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:external-link" {...props}></Icon>
