<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agaqwoz2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agaqwoz2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:document-layout-center" {...props}></Icon>
