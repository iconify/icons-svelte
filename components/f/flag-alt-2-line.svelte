<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc8eo5pxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc8eo5pxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flag-alt-2-line" {...props}></Icon>
