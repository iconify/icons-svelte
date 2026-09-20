<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7-dn10az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7-dn10az"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:compare-remove" {...props}></Icon>
