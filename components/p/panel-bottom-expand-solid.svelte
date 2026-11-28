<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz9u0m0if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz9u0m0if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:panel-bottom-expand-solid" {...props}></Icon>
