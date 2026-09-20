<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7pve-3mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7pve-3mm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:road-alt" {...props}></Icon>
