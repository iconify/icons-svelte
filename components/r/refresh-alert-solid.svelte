<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxm1gvbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxm1gvbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:refresh-alert-solid" {...props}></Icon>
