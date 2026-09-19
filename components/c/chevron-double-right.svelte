<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve6u0vqil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve6u0vqil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-double-right" {...props}></Icon>
