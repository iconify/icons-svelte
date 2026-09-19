<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lclse37hi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lclse37hi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:close-circle-2-bold" {...props}></Icon>
