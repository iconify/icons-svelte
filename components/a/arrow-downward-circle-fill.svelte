<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-81habpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h-81habpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-downward-circle-fill" {...props}></Icon>
