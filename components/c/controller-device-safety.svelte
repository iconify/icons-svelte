<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1zokhhls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1zokhhls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:controller-device-safety" {...props}></Icon>
