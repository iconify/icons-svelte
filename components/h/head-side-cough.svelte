<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaeycfbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aaeycfbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:head-side-cough" {...props}></Icon>
