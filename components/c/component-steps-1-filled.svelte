<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h13l7zvxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h13l7zvxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:component-steps-1-filled" {...props}></Icon>
