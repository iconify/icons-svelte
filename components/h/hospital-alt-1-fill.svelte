<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swl0_-bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="swl0_-bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:hospital-alt-1-fill" {...props}></Icon>
