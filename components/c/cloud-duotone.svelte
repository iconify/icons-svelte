<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_u455h9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_u455h9j primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-duotone" {...props}></Icon>
