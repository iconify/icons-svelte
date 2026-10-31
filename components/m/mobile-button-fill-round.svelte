<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2oqqhw1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2oqqhw1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mobile-button-fill-round" {...props}></Icon>
