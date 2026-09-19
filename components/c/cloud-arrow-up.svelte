<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5lo8smcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5lo8smcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:cloud-arrow-up" {...props}></Icon>
