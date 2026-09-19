<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8z9qwbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8z9qwbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:globe-2-fill" {...props}></Icon>
