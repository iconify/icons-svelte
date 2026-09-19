<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej74ic_ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej74ic_ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:ellipsis-vertical" {...props}></Icon>
