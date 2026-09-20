<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3sot2bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3sot2bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:page-separator" {...props}></Icon>
