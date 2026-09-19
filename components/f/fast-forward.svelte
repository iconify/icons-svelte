<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y30k_otqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y30k_otqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:fast-forward" {...props}></Icon>
