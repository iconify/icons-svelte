<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suw-znhgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suw-znhgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-up-solid" {...props}></Icon>
