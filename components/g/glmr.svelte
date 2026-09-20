<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3dbbuu7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3dbbuu7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:glmr" {...props}></Icon>
