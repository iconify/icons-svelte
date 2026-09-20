<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfz-8ubyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfz-8ubyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-tick" {...props}></Icon>
